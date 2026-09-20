<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl5vce1kb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tl5vce1kb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:koyeb" {...props}></Icon>
