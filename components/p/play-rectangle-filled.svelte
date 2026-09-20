<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vws7xf1nk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vws7xf1nk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:play-rectangle-filled" {...props}></Icon>
