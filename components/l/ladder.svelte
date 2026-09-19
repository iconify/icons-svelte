<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyuovud_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yyuovud_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:ladder" {...props}></Icon>
