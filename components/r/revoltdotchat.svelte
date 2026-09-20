<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-_v0x0lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-_v0x0lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:revoltdotchat" {...props}></Icon>
