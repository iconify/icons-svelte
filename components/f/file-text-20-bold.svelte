<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8im5qk_h.css';
import '../../css/q/qbo1mkbwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w8im5qk_h"/><path class="qbo1mkbwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-text-20-bold" {...props}></Icon>
