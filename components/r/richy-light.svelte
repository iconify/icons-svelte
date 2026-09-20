<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4p0j-rha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e4p0j-rha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:richy-light" {...props}></Icon>
