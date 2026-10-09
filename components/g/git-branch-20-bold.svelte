<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do4ne9uns.css';
import '../../css/j/j89f_0dyx.css';
import '../../css/b/b6j267ddl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="do4ne9uns"/><path class="j89f_0dyx"/><path class="b6j267ddl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:git-branch-20-bold" {...props}></Icon>
