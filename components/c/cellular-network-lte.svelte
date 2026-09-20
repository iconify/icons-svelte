<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd178qyhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xd178qyhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cellular-network-lte" {...props}></Icon>
