<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fos5kccae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fos5kccae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ros" {...props}></Icon>
