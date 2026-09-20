<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so2i40b2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="so2i40b2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ferris-wheel-bold" {...props}></Icon>
