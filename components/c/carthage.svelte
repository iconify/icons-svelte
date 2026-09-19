<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcigu4nvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wcigu4nvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:carthage" {...props}></Icon>
