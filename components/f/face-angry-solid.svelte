<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yth3gxboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yth3gxboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:face-angry-solid" {...props}></Icon>
