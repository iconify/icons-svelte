<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnndfeb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnndfeb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:battery-indicator" {...props}></Icon>
