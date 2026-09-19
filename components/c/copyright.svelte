<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0h_kbs6z.css';
import '../../css/i/i10epfbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0h_kbs6z"/><path class="i10epfbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:copyright" {...props}></Icon>
