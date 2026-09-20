<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl0md4byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nl0md4byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ragged-flag-with-skull" {...props}></Icon>
