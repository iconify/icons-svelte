<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msb5ggxnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="msb5ggxnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:gyrophare" {...props}></Icon>
