<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7ses8b9s.css';
import '../../css/s/su9n4xbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7ses8b9s"/><path clip-rule="evenodd" class="su9n4xbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:key-minimalistic-square-2-bold" {...props}></Icon>
