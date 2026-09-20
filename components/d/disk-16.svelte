<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chj_3ab-w.css';
import '../../css/v/v97disbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="chj_3ab-w"/><path clip-rule="evenodd" class="v97disbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:disk-16" {...props}></Icon>
