<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq-54j8na.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="xq-54j8na"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:city-alt" {...props}></Icon>
