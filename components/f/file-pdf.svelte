<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6t7jkbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="k6t7jkbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:file-pdf" {...props}></Icon>
