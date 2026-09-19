<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spjx-7o2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="spjx-7o2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:band-aid" {...props}></Icon>
