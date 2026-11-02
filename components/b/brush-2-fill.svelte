<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwiktzbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwiktzbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:brush-2-fill" {...props}></Icon>
