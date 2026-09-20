<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iakl_ubig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iakl_ubig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mobile-navigation-filled" {...props}></Icon>
