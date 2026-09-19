<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq54d0bhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vq54d0bhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:editor-break" {...props}></Icon>
