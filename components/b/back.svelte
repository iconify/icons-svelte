<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7bk3wbqk.css';
import '../../css/r/r7lg6bmas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o7bk3wbqk"/><path class="r7lg6bmas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:back" {...props}></Icon>
