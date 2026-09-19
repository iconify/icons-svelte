<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmbxl9aac.css';
import '../../css/z/z7rr8ngug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dmbxl9aac"/><path class="z7rr8ngug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:return-down-forward-outline" {...props}></Icon>
