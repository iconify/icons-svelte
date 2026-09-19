<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1t1bndoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1t1bndoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:chip-filled" {...props}></Icon>
