<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj0q8nbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rj0q8nbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:bug-solid" {...props}></Icon>
