<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-6-mabzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-6-mabzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:location-pin-plus-filled" {...props}></Icon>
