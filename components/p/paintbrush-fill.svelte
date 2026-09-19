<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh0lcaceg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="qh0lcaceg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:paintbrush-fill" {...props}></Icon>
