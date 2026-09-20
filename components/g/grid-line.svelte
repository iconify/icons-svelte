<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfe96abzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfe96abzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:grid-line" {...props}></Icon>
