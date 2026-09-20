<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z21m6mbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z21m6mbuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-translate" {...props}></Icon>
