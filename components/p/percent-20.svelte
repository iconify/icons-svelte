<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0vjpuw4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o0vjpuw4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:percent-20" {...props}></Icon>
