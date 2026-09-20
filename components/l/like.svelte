<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdeuh0_pp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sdeuh0_pp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:like" {...props}></Icon>
