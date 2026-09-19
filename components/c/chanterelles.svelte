<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6e4s3bwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s6e4s3bwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:chanterelles" {...props}></Icon>
