<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv-z9s63g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="cv-z9s63g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:brightness-3" {...props}></Icon>
