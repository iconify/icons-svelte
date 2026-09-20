<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad2r3cjik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ad2r3cjik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:folder-check-line" {...props}></Icon>
