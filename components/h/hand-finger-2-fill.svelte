<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea0-w_xym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ea0-w_xym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hand-finger-2-fill" {...props}></Icon>
