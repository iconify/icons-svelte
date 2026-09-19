<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn2rnrqnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="yn2rnrqnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:earth-africa" {...props}></Icon>
