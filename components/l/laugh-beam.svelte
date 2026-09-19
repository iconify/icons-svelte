<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmts52bbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="tmts52bbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:laugh-beam" {...props}></Icon>
