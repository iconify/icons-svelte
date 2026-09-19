<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzrc6-c5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzrc6-c5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:align-justify" {...props}></Icon>
