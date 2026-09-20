<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8i2mzbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8i2mzbyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:g2g" {...props}></Icon>
