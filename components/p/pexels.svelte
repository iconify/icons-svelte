<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inn4uxbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="inn4uxbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:pexels" {...props}></Icon>
