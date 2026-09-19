<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je-u0bcmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="je-u0bcmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:hare" {...props}></Icon>
