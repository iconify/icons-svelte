<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkvp4dvmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="vkvp4dvmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:chevron-right-circle" {...props}></Icon>
