<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7qfvb_xp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7qfvb_xp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dmm" {...props}></Icon>
