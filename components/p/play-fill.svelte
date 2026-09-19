<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9z5x9uch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="z9z5x9uch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:play-fill" {...props}></Icon>
