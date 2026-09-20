<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivnivebxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivnivebxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:alarm-off-filled" {...props}></Icon>
