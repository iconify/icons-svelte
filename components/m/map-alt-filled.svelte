<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llsy4sbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llsy4sbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:map-alt-filled" {...props}></Icon>
