<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_e6fpqvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x_e6fpqvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:paragraph" {...props}></Icon>
