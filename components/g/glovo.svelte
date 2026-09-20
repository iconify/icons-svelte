<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg1z77b5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fg1z77b5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:glovo" {...props}></Icon>
