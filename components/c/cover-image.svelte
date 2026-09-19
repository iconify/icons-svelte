<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgbu0syiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vgbu0syiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:cover-image" {...props}></Icon>
