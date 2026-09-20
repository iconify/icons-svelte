<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu604iz0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu604iz0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:forward-2-broken" {...props}></Icon>
