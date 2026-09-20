<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gls5yonhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gls5yonhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:adobecreativecloud" {...props}></Icon>
