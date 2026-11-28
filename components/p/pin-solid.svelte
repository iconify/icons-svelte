<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifjxbgbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifjxbgbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pin-solid" {...props}></Icon>
