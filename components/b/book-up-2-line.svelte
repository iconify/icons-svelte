<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm_8amnbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm_8amnbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-up-2-line" {...props}></Icon>
