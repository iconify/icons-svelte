<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn9p7b49h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kn9p7b49h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-right-up-bold" {...props}></Icon>
