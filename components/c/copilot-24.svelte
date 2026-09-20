<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnmcfvtyh.css';
import '../../css/a/axqd7-lja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnmcfvtyh"/><path class="axqd7-lja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:copilot-24" {...props}></Icon>
