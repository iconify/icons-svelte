<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh1s9nbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lh1s9nbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:refrigerator" {...props}></Icon>
