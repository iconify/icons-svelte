<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-1dadcot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u-1dadcot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:reload" {...props}></Icon>
