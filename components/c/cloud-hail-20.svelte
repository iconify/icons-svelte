<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwfe8ub8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mwfe8ub8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-hail-20" {...props}></Icon>
