<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxm6xjm4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxm6xjm4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clipboard-close-fill-round" {...props}></Icon>
