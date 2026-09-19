<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glysl4b1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glysl4b1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:basketball" {...props}></Icon>
