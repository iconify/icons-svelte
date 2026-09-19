<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0_lmmbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":954};
const content = `<path class="p0_lmmbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:bar" {...props}></Icon>
