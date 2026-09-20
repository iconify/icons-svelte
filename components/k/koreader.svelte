<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su-hxbbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="su-hxbbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:koreader" {...props}></Icon>
