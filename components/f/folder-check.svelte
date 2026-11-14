<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad9e7wz3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ad9e7wz3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folder-check" {...props}></Icon>
