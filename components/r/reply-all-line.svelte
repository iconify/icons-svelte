<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi51nac0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gi51nac0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:reply-all-line" {...props}></Icon>
