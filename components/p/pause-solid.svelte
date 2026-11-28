<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc7yqrbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zc7yqrbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pause-solid" {...props}></Icon>
