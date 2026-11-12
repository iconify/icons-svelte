<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzg3y5byu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xzg3y5byu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jekyll-dark" {...props}></Icon>
