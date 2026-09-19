<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd1gm5b2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":32};
const content = `<path class="hd1gm5b2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:cloud" {...props}></Icon>
