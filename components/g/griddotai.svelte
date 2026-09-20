<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygpmz9qhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygpmz9qhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:griddotai" {...props}></Icon>
