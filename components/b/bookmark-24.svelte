<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9gx19_go.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9gx19_go"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:bookmark-24" {...props}></Icon>
