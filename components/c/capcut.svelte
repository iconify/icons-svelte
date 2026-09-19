<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx8xjnb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qx8xjnb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:capcut" {...props}></Icon>
