<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw-jeeboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zw-jeeboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layers-horizontal-solid" {...props}></Icon>
