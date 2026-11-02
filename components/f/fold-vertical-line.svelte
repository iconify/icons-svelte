<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fku2rgopk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fku2rgopk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fold-vertical-line" {...props}></Icon>
