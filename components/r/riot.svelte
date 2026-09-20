<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnolvzexl.css';
import '../../css/a/ag8wbubia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pnolvzexl"/><path class="ag8wbubia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:riot" {...props}></Icon>
