<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyvqkcc0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="dyvqkcc0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:caret-square-left" {...props}></Icon>
