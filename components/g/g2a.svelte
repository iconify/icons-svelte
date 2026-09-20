<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueg6d4b6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ueg6d4b6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:g2a" {...props}></Icon>
