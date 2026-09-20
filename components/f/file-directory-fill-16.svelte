<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-n6sx-7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e-n6sx-7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-directory-fill-16" {...props}></Icon>
