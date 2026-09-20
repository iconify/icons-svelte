<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfyst0acy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hfyst0acy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:a-frame-tent" {...props}></Icon>
