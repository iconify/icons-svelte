<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_oajib1w.css';
import '../../css/m/mur108jyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_oajib1w"/><path class="mur108jyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-arrow-down" {...props}></Icon>
