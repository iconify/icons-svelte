<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3re1va3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3re1va3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:dots-vertical-hexagon-solid" {...props}></Icon>
