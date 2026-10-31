<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3-a3w-3w.css';
import '../../css/l/lonxz_wlc.css';
import '../../css/k/kj18kdbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="c3-a3w-3w"/><path class="lonxz_wlc"/><path class="kj18kdbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:ivory-coast" {...props}></Icon>
