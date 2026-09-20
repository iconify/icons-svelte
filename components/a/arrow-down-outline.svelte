<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8g_y9igt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q8g_y9igt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-down-outline" {...props}></Icon>
