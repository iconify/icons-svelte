<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l628z4bbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l628z4bbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:freelancermap" {...props}></Icon>
