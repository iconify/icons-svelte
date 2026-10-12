<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3m5nx0ys.css';
import '../../css/u/u2i0qcb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o3m5nx0ys"/><path class="u2i0qcb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:note-pencil-fill-20" {...props}></Icon>
