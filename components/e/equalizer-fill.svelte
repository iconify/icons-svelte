<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygd8jqbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygd8jqbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:equalizer-fill" {...props}></Icon>
