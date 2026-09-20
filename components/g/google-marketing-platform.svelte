<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp150ubed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wp150ubed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-marketing-platform" {...props}></Icon>
