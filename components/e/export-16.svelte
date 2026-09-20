<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr1tfnb7u.css';
import '../../css/g/gnwbtmb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xr1tfnb7u"/><path class="gnwbtmb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:export-16" {...props}></Icon>
