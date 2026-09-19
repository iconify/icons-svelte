<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jovidffuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jovidffuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:ban" {...props}></Icon>
