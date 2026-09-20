<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jysc-acmf.css';
import '../../css/f/flr8mw1dg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jysc-acmf"/><path class="flr8mw1dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:html3" {...props}></Icon>
