<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i43fwks-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i43fwks-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bsd" {...props}></Icon>
