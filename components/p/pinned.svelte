<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/got3ckffi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="got3ckffi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:pinned" {...props}></Icon>
