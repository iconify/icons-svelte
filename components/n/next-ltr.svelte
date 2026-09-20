<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfq4g4h5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zfq4g4h5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:next-ltr" {...props}></Icon>
