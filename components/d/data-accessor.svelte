<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs4ufqbdt.css';
import '../../css/d/dlp7nstpk.css';
import '../../css/x/x2k2a8bfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fs4ufqbdt"/><circle class="dlp7nstpk"/><path class="x2k2a8bfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-accessor" {...props}></Icon>
