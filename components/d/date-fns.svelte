<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km3_h9but.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km3_h9but"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:date-fns" {...props}></Icon>
