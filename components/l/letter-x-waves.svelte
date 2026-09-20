<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acut2rbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acut2rbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-x-waves" {...props}></Icon>
