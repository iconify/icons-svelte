<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc5cwfboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rc5cwfboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:github" {...props}></Icon>
