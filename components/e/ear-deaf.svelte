<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md5cdnbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="md5cdnbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:ear-deaf" {...props}></Icon>
