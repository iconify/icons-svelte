<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f97e5f--j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f97e5f--j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:alpine" {...props}></Icon>
