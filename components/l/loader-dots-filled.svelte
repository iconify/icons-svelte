<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdebumt5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdebumt5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:loader-dots-filled" {...props}></Icon>
