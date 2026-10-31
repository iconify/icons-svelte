<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8dfhgbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8dfhgbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:link-vertical-fill-round" {...props}></Icon>
