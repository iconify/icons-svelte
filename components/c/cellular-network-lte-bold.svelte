<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zatiqxfju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zatiqxfju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cellular-network-lte-bold" {...props}></Icon>
