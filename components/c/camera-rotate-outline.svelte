<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yul2wvb3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yul2wvb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:camera-rotate-outline" {...props}></Icon>
