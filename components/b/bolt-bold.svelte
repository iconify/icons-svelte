<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzef3x4zs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzef3x4zs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bolt-bold" {...props}></Icon>
