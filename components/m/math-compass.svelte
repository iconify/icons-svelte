<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1zx5f6ip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1zx5f6ip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:math-compass" {...props}></Icon>
