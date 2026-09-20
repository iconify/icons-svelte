<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb-4nob7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sb-4nob7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:link-2-off-fill" {...props}></Icon>
