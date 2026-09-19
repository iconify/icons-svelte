<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf4u1os6q.css';
import '../../css/y/yxsbj3jnf.css';
import '../../css/e/edskbpa8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="tf4u1os6q"><path class="yxsbj3jnf"/><path class="edskbpa8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:angular-guard" {...props}></Icon>
