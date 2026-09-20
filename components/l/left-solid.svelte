<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6vv8jbpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l6vv8jbpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:left-solid" {...props}></Icon>
