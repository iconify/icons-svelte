<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xph2au4ll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xph2au4ll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:element" {...props}></Icon>
