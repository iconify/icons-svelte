<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi4my1vub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wi4my1vub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:libuv" {...props}></Icon>
