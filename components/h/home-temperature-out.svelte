<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxo7j6bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxo7j6bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:home-temperature-out" {...props}></Icon>
