<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-3hur0vy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e-3hur0vy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-point-favourite-outline" {...props}></Icon>
