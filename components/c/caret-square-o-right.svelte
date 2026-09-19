<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru0o-1bas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<g transform="translate(1536 0) scale(-1 1)"><path class="ru0o-1bas"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:caret-square-o-right" {...props}></Icon>
