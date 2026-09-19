<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7vmeuosh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":192,"height":512};
const content = `<path class="s7vmeuosh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:caret-right" {...props}></Icon>
