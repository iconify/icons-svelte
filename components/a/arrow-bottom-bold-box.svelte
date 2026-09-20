<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0dvk7b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0dvk7b2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-bottom-bold-box" {...props}></Icon>
