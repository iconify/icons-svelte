<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbu26itox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lbu26itox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-directory-16" {...props}></Icon>
