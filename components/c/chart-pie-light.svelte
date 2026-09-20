<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctceaps1p.css';
import '../../css/y/yg4acmb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctceaps1p"/><path class="yg4acmb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:chart-pie-light" {...props}></Icon>
