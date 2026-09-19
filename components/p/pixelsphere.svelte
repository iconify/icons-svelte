<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu0__ibun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hu0__ibun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pixelsphere" {...props}></Icon>
