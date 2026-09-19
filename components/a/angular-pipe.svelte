<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf4u1os6q.css';
import '../../css/f/f-8rhabij.css';
import '../../css/e/edskbpa8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="tf4u1os6q"><path class="f-8rhabij"/><path class="edskbpa8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:angular-pipe" {...props}></Icon>
