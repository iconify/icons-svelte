<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp52g3bbs.css';
import '../../css/v/vkaphjdbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fp52g3bbs"/><path class="vkaphjdbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:license" {...props}></Icon>
