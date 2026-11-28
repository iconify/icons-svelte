<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dny39646t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="dny39646t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:ethernet-light" {...props}></Icon>
