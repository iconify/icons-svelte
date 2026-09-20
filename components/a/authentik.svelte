<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejc_0y43h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejc_0y43h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:authentik" {...props}></Icon>
