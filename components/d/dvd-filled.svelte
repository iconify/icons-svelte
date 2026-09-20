<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs3tcib1t.css';
import '../../css/e/e8yz86-ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gs3tcib1t"/><path class="e8yz86-ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:dvd-filled" {...props}></Icon>
