<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz_-kvbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":656};
const content = `<path class="oz_-kvbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:reply" {...props}></Icon>
