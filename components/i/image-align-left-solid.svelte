<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikea9glqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikea9glqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:image-align-left-solid" {...props}></Icon>
