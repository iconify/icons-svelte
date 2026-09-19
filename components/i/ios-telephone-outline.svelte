<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io65_osja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="io65_osja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-telephone-outline" {...props}></Icon>
