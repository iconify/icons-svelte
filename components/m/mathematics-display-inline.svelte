<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqqdg9bxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bqqdg9bxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:mathematics-display-inline" {...props}></Icon>
