<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl-3szpmw.css';
import '../../css/g/g_0ul0b0z.css';
import '../../css/g/gnu88kuoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bl-3szpmw"/><path class="g_0ul0b0z"/><path class="gnu88kuoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:group" {...props}></Icon>
