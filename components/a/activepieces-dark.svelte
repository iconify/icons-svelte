<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/heu0qx0oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="heu0qx0oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:activepieces-dark" {...props}></Icon>
