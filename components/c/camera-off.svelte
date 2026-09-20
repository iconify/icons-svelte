<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umjehrbzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umjehrbzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:camera-off" {...props}></Icon>
