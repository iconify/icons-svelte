<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo-ux8bhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":961,"height":960};
const content = `<path class="fo-ux8bhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:dominofive" {...props}></Icon>
