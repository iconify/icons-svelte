<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tud7q3bev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tud7q3bev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-u-turn-left-line-solid" {...props}></Icon>
