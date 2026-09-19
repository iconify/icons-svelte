<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3pbgcg6r.css';
import '../../css/e/e052tbbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="z3pbgcg6r"/><path class="e052tbbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:down" {...props}></Icon>
