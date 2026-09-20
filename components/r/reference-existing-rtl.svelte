<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f94x20bnf.css';
import '../../css/u/u7syfkble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f94x20bnf"/><path class="u7syfkble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:reference-existing-rtl" {...props}></Icon>
