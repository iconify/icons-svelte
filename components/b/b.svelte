<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohg5shbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ohg5shbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:b" {...props}></Icon>
