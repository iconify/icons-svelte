<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi_ndpbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hi_ndpbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:down" {...props}></Icon>
