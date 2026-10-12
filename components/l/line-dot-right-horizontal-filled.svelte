<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd8anyb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rd8anyb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:line-dot-right-horizontal-filled" {...props}></Icon>
