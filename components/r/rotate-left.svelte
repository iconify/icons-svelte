<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdek8tbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdek8tbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:rotate-left" {...props}></Icon>
