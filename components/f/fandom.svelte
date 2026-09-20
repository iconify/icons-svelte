<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn_23tb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mn_23tb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fandom" {...props}></Icon>
