<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-jsh9bpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-jsh9bpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoji-koala" {...props}></Icon>
