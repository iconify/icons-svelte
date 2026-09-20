<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0u3bcc6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0u3bcc6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-o-circle" {...props}></Icon>
