<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7-al5b6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="n7-al5b6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:memory" {...props}></Icon>
