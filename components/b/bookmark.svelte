<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s42s__biu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="s42s__biu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:bookmark" {...props}></Icon>
