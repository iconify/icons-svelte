<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkczs_bkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkczs_bkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:dice-1" {...props}></Icon>
