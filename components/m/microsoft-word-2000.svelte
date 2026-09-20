<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5qmmgbfo.css';
import '../../css/p/p-r-fqbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i5qmmgbfo"/><path class="p-r-fqbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-word-2000" {...props}></Icon>
