<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isnxa6b2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isnxa6b2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cursor-cell-filled" {...props}></Icon>
