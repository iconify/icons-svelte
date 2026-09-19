<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf44ky2lr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tf44ky2lr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:file-x-filled" {...props}></Icon>
