<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbgo2sbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbgo2sbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gnu" {...props}></Icon>
