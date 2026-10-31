<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap8e4tb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ap8e4tb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-lock-corner-fill-round" {...props}></Icon>
