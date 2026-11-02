<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhj__jb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhj__jb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:more-2-line" {...props}></Icon>
