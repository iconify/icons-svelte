<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkdiej8jg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pkdiej8jg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:camera-rotate" {...props}></Icon>
