<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_ieabb_g.css';
import '../../css/r/r2qotkj1w.css';
import '../../css/i/i1958g00u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_ieabb_g"/><rect class="r2qotkj1w"/><path class="i1958g00u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:document-layout-left" {...props}></Icon>
