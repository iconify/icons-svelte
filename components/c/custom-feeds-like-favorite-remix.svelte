<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdou84mty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vdou84mty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:custom-feeds-like-favorite-remix" {...props}></Icon>
