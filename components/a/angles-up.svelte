<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx-bmy_tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="yx-bmy_tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:angles-up" {...props}></Icon>
