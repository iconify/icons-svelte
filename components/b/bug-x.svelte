<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wut467bix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wut467bix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bug-x" {...props}></Icon>
