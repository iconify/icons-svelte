<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3t-t7xoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n3t-t7xoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:angle-double-up-solid" {...props}></Icon>
