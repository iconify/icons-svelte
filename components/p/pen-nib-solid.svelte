<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb0l2eb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pb0l2eb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:pen-nib-solid" {...props}></Icon>
