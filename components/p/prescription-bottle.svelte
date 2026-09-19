<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bti3klb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="bti3klb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:prescription-bottle" {...props}></Icon>
