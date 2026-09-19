<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aek238bvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="aek238bvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:mars-stroke-right" {...props}></Icon>
