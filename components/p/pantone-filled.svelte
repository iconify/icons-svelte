<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqmj2n7us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqmj2n7us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:pantone-filled" {...props}></Icon>
