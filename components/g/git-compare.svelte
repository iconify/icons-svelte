<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz9097b4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rz9097b4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:git-compare" {...props}></Icon>
