<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp7zcibmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bp7zcibmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:baguette-bread" {...props}></Icon>
