<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5pateyts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5pateyts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folder-03" {...props}></Icon>
