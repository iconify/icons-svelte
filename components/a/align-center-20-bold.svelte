<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv-71uxns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qv-71uxns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:align-center-20-bold" {...props}></Icon>
