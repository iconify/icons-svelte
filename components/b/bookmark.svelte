<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrwfk1bik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="zrwfk1bik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:bookmark" {...props}></Icon>
