<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk8l4sozy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wk8l4sozy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:monogame" {...props}></Icon>
