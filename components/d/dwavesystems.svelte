<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybu4mabje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybu4mabje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:dwavesystems" {...props}></Icon>
