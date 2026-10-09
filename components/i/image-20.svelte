<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wetq5b_1u.css';
import '../../css/y/ysix8mbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wetq5b_1u"/><path class="ysix8mbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:image-20" {...props}></Icon>
