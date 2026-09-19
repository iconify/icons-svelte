<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am2uaik4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="am2uaik4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-right-2" {...props}></Icon>
