<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgglibcip.css';
import '../../css/o/op65_9z-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jgglibcip"/><path clip-rule="evenodd" class="op65_9z-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:file-markdown-16" {...props}></Icon>
