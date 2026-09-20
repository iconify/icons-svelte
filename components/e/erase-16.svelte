<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-gd7u-dq.css';
import '../../css/a/a6o68sb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x-gd7u-dq"/><path clip-rule="evenodd" class="a6o68sb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:erase-16" {...props}></Icon>
