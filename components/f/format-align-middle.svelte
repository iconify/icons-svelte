<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag7bil92h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ag7bil92h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:format-align-middle" {...props}></Icon>
