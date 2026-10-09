<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq_e-jbll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dq_e-jbll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:diamond-20" {...props}></Icon>
