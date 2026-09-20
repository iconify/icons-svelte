<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbb9tbcfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gbb9tbcfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:oven-mitts" {...props}></Icon>
