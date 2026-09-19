<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geuk91bla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="geuk91bla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:funeral-urn" {...props}></Icon>
