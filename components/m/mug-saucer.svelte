<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w18gdbbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="w18gdbbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:mug-saucer" {...props}></Icon>
