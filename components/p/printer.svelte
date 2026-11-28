<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbrgkcbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbrgkcbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:printer" {...props}></Icon>
