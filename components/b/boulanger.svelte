<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb-b_1_ij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gb-b_1_ij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:boulanger" {...props}></Icon>
