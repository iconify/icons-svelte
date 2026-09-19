<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbnu52b5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="zbnu52b5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:helicopter-symbol" {...props}></Icon>
