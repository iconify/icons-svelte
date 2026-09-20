<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue99ppw5a.css';
import '../../css/s/sach5mb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ue99ppw5a"/><path class="sach5mb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:left-right-black-arrow" {...props}></Icon>
