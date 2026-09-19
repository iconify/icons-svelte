<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eed4xfb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="eed4xfb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:hare-fill" {...props}></Icon>
