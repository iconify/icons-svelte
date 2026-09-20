<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di5dbun5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="di5dbun5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:image-plus-line" {...props}></Icon>
