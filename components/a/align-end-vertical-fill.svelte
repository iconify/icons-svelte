<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5gg4sb7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5gg4sb7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-end-vertical-fill" {...props}></Icon>
