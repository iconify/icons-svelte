<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_vkuub1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v_vkuub1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bookmark-square-minimalistic-outline" {...props}></Icon>
