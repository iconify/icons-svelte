<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8fi9kbtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d8fi9kbtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ada" {...props}></Icon>
