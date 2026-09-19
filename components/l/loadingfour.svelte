<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcx4fbfjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fcx4fbfjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:loadingfour" {...props}></Icon>
