<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw82_714f.css';
import '../../css/y/ysy1t6bhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer tw82_714f"/><path class="duoicon-primary-layer ysy1t6bhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:camera-square" {...props}></Icon>
