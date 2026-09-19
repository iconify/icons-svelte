<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f51nmvb9n.css';
import '../../css/t/t2aiwobxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f51nmvb9n"/><path class="t2aiwobxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:folder-shared" {...props}></Icon>
