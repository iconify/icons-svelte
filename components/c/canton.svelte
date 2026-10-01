<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vof7ihrjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vof7ihrjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:canton" {...props}></Icon>
