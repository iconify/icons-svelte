<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk9dx8b8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="pk9dx8b8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:image-file" {...props}></Icon>
