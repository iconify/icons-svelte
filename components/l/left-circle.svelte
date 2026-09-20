<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiz2zc2mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aiz2zc2mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:left-circle" {...props}></Icon>
