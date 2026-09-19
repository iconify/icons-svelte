<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru7yyeoqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path clip-rule="evenodd" class="ru7yyeoqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:ram" {...props}></Icon>
