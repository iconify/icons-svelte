<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r57wg7cwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r57wg7cwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-baguette" {...props}></Icon>
