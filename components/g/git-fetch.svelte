<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjd_c8fym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sjd_c8fym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:git-fetch" {...props}></Icon>
