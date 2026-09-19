<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu-vy3n-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xu-vy3n-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:renren" {...props}></Icon>
