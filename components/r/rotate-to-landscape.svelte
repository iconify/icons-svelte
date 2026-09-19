<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jewwt-x9z.css';
import '../../css/j/j02m59mzy.css';
import '../../css/c/cy0djhbhr.css';
import '../../css/h/htogyc_on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jewwt-x9z"/><path class="j02m59mzy"/><path class="cy0djhbhr"/><path class="htogyc_on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:rotate-to-landscape" {...props}></Icon>
