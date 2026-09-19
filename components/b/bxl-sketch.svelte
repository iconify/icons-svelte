<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn2ia_bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nn2ia_bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-sketch" {...props}></Icon>
