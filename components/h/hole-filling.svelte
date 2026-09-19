<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt8jb-7jt.css';
import '../../css/v/v3_7cbqjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="yt8jb-7jt"/><path class="v3_7cbqjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:hole-filling" {...props}></Icon>
