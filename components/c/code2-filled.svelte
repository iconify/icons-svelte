<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li_5nlrrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="li_5nlrrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:code2-filled" {...props}></Icon>
