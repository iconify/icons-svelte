<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4rpuubib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4rpuubib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:fullscreen-filled" {...props}></Icon>
