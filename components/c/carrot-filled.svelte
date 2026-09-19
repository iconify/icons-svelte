<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2t6debfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2t6debfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:carrot-filled" {...props}></Icon>
