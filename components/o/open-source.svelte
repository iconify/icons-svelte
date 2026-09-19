<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt5hs-bhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gt5hs-bhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:open-source" {...props}></Icon>
