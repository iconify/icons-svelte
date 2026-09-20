<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c17dyebzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c17dyebzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-classical-building-with-flag" {...props}></Icon>
