<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su-chh5bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="su-chh5bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:fareneight" {...props}></Icon>
