<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf4u1os6q.css';
import '../../css/p/ptw7wyouw.css';
import '../../css/e/edskbpa8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="tf4u1os6q"><path class="ptw7wyouw"/><path class="edskbpa8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:angular-service" {...props}></Icon>
