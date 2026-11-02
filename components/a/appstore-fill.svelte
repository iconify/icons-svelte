<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0qz2gbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0qz2gbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:appstore-fill" {...props}></Icon>
