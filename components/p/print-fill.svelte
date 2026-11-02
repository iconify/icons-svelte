<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1lw0cctn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a1lw0cctn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:print-fill" {...props}></Icon>
