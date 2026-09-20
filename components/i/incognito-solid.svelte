<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0a_tmbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0a_tmbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:incognito-solid" {...props}></Icon>
