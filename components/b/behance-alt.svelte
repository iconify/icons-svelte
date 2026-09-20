<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/raf-j67xd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="raf-j67xd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:behance-alt" {...props}></Icon>
