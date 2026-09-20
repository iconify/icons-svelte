<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loe9jibay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="loe9jibay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:music-slider2-filled" {...props}></Icon>
