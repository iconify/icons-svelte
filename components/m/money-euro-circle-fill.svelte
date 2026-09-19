<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f00vbwb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="f00vbwb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:money-euro-circle-fill" {...props}></Icon>
