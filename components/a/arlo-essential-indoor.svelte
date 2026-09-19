<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9jziobae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9jziobae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:arlo-essential-indoor" {...props}></Icon>
