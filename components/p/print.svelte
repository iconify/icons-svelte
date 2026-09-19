<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbb25_i0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nbb25_i0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:print" {...props}></Icon>
