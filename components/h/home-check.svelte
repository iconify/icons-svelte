<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbv-0-bzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbv-0-bzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:home-check" {...props}></Icon>
