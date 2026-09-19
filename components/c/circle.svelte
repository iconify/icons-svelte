<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkxjx-nwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="qkxjx-nwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:circle" {...props}></Icon>
