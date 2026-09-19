<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko5rs75hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ko5rs75hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:bacterium" {...props}></Icon>
