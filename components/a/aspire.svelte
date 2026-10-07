<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rodc2fbdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="rodc2fbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:aspire" {...props}></Icon>
