<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r96o9m0kk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="r96o9m0kk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:check" {...props}></Icon>
