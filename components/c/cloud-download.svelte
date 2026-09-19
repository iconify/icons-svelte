<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyyr9brib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyyr9brib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:cloud-download" {...props}></Icon>
