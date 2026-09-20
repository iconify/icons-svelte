<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrks0fbpf.css';
import '../../css/e/e4zfowz9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="mrks0fbpf"/><path class="e4zfowz9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:combining-enclosing-keycap" {...props}></Icon>
