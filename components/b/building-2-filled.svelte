<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgjm7j-sy.css';
import '../../css/v/vi5e0ubjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgjm7j-sy"/><path class="vi5e0ubjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:building-2-filled" {...props}></Icon>
