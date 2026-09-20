<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5xia0bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z5xia0bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:page-setup-2-16" {...props}></Icon>
