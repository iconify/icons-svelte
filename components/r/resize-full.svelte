<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d48o06bxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="d48o06bxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:resize-full" {...props}></Icon>
