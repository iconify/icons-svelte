<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t58ktzpqn.css';
import '../../css/h/hai_nbocs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t58ktzpqn"/><path clip-rule="evenodd" class="hai_nbocs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:instagram-fill-16" {...props}></Icon>
