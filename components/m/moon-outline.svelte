<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lphe4gxwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lphe4gxwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:moon-outline" {...props}></Icon>
