<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytl8wsbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytl8wsbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:capture" {...props}></Icon>
