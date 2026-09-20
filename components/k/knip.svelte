<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzlj61byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzlj61byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:knip" {...props}></Icon>
