<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg-xvcycj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg-xvcycj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chart-bar" {...props}></Icon>
