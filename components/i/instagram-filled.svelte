<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyhatftlr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="oyhatftlr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:instagram-filled" {...props}></Icon>
