<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kald952wg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="kald952wg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:cube" {...props}></Icon>
