<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3-tx0tsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="y3-tx0tsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:paperclip" {...props}></Icon>
