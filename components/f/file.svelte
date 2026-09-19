<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1we_sbru.css';
import '../../css/w/wo3zs2b-t.css';
import '../../css/j/j06su1bbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a1we_sbru"/><path class="wo3zs2b-t"/><path class="j06su1bbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:file" {...props}></Icon>
