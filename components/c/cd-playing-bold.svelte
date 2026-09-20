<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u--3evbhh.css';
import '../../css/l/lseytrb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u--3evbhh"/><path class="lseytrb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cd-playing-bold" {...props}></Icon>
