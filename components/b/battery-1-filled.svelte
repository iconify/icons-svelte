<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bin6v8b5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bin6v8b5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:battery-1-filled" {...props}></Icon>
