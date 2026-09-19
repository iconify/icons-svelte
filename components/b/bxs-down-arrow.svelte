<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppbj-acta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ppbj-acta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-down-arrow" {...props}></Icon>
