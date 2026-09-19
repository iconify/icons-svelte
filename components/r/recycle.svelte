<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4_6nhbxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1728};
const content = `<path class="y4_6nhbxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:recycle" {...props}></Icon>
