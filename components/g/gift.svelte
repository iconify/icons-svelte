<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0qt1i8jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h0qt1i8jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:gift" {...props}></Icon>
