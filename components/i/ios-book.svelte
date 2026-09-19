<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l99r3d5dl.css';
import '../../css/a/a4x7enbjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l99r3d5dl"/><path class="a4x7enbjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-book" {...props}></Icon>
