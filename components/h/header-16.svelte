<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdidb4b8e.css';
import '../../css/j/jt195abqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zdidb4b8e"/><path clip-rule="evenodd" class="jt195abqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:header-16" {...props}></Icon>
