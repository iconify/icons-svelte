<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpo_5g0im.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpo_5g0im"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kik" {...props}></Icon>
