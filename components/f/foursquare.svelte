<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxot5i1qh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxot5i1qh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:foursquare" {...props}></Icon>
