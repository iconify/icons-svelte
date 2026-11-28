<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q16dfk8ej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="q16dfk8ej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:caret-down-up-thin" {...props}></Icon>
