<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_ng6supk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_ng6supk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flag-4-off-fill" {...props}></Icon>
