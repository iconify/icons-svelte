<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av7c2sb3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av7c2sb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:italic-solid" {...props}></Icon>
