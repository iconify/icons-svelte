<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zik2nzbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zik2nzbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clock-9-round" {...props}></Icon>
