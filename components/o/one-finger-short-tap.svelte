<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se0z4cciz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="se0z4cciz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:one-finger-short-tap" {...props}></Icon>
