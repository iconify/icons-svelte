<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxclktjqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxclktjqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:etc" {...props}></Icon>
