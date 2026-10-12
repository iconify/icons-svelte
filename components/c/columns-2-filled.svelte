<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj0bay9ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj0bay9ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:columns-2-filled" {...props}></Icon>
