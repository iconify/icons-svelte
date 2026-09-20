<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khsak6icn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="khsak6icn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:monitor-lines" {...props}></Icon>
