<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc-pl27ds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="cc-pl27ds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:laptop-house" {...props}></Icon>
