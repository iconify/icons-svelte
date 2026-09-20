<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul_tz0b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ul_tz0b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:calibre" {...props}></Icon>
