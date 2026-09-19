<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blkabsbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="blkabsbon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:landmark" {...props}></Icon>
