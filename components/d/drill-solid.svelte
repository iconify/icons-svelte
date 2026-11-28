<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv4mr3b9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wv4mr3b9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:drill-solid" {...props}></Icon>
