<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hiyr906ts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hiyr906ts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:brand-youtube-solid" {...props}></Icon>
