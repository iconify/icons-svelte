<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q13w98l5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q13w98l5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-2-fill" {...props}></Icon>
