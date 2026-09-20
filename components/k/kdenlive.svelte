<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrg2wkbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrg2wkbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kdenlive" {...props}></Icon>
