<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdh0n-k9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdh0n-k9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-top-left-alt" {...props}></Icon>
