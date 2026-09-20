<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnxtu2a1f.css';
import '../../css/p/pt_8qebbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wnxtu2a1f"/><path clip-rule="evenodd" class="pt_8qebbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:cutter-16" {...props}></Icon>
