<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yluilwbrm.css';
import '../../css/t/tjuixfu3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yluilwbrm"/><path class="tjuixfu3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:keep-dry" {...props}></Icon>
