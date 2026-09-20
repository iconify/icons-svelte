<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlrh-ubaa.css';
import '../../css/u/u13yqv0ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlrh-ubaa"/><path class="u13yqv0ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:low-temperature-line" {...props}></Icon>
