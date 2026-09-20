<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wacwgubxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wacwgubxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:devrant" {...props}></Icon>
