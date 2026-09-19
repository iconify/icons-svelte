<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1rre3sqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="i1rre3sqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:glasses" {...props}></Icon>
