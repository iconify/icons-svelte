<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2dvr6buw.css';
import '../../css/x/xw7gk0pnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2dvr6buw"/><path class="xw7gk0pnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:camera-filled" {...props}></Icon>
