<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfweduw3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lfweduw3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bluetooth-outline" {...props}></Icon>
