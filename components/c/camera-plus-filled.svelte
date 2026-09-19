<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqtjih4ab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqtjih4ab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:camera-plus-filled" {...props}></Icon>
