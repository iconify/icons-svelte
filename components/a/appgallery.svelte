<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk9_r652x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dk9_r652x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:appgallery" {...props}></Icon>
