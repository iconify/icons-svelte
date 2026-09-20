<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a808n44vh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a808n44vh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jekyll-light" {...props}></Icon>
