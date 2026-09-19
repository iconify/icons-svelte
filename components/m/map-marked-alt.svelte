<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5qlwgbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="i5qlwgbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:map-marked-alt" {...props}></Icon>
