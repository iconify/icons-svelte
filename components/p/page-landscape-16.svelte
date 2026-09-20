<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-2m00b1v.css';
import '../../css/a/a9p3m-d8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u-2m00b1v"/><path clip-rule="evenodd" class="a9p3m-d8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:page-landscape-16" {...props}></Icon>
