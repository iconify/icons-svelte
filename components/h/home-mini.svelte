<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8u2jbc4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8u2jbc4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:home-mini" {...props}></Icon>
