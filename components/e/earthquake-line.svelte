<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3c2kqz_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3c2kqz_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:earthquake-line" {...props}></Icon>
