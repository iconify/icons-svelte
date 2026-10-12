<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw15abcyx.css';
import '../../css/d/d2sisx8fh.css';
import '../../css/j/jge7z1bbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pw15abcyx"/><path class="d2sisx8fh"/><path class="jge7z1bbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:angle-grinder-48" {...props}></Icon>
