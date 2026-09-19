<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0i5ohb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0i5ohb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:computer-retro-filled" {...props}></Icon>
