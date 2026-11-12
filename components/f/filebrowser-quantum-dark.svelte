<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9t-uvgki.css';
import '../../css/j/j90iobcke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v9t-uvgki"/><path class="j90iobcke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:filebrowser-quantum-dark" {...props}></Icon>
