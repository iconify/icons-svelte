<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw6ppnbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="iw6ppnbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:next" {...props}></Icon>
