<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo1wx0kvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="oo1wx0kvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:bowl-rice" {...props}></Icon>
