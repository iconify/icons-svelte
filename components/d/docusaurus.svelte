<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf4u1os6q.css';
import '../../css/e/euvn5gkav.css';
import '../../css/r/r2aeg49cb.css';
import '../../css/a/a6nvfqtpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="tf4u1os6q"><path class="euvn5gkav"/><path class="r2aeg49cb"/><path class="a6nvfqtpq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:docusaurus" {...props}></Icon>
