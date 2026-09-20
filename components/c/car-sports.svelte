<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0qylfb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0qylfb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-sports" {...props}></Icon>
