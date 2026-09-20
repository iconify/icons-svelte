<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/baev--_qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="baev--_qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-right-down-circle-line" {...props}></Icon>
