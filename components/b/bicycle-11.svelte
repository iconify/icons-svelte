<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzur78bxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="fzur78bxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:bicycle-11" {...props}></Icon>
