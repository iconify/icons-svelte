<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-s9xac3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-s9xac3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:align-image-left" {...props}></Icon>
