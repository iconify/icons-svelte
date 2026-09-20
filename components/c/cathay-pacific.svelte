<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrwqzibld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26.458,"height":3.704};
const content = `<path class="yrwqzibld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cathay-pacific" {...props}></Icon>
