<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs8_8nb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vs8_8nb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:logo-meta-wiki" {...props}></Icon>
