<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsvdh243j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsvdh243j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:anticlockwise-filled" {...props}></Icon>
