<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cny6ftb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cny6ftb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:clock-pause" {...props}></Icon>
