<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egc-prmmk.css';
import '../../css/y/y4_kabc3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="egc-prmmk"/><path class="y4_kabc3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:file-movie-filled" {...props}></Icon>
