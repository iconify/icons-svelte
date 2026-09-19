<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0bv7wbdk.css';
import '../../css/g/g2_5sshgx.css';
import '../../css/j/j1xfmgbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="n0bv7wbdk"><path class="g2_5sshgx"/><circle class="j1xfmgbrg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:dub" {...props}></Icon>
