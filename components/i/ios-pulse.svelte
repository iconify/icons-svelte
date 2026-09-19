<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu5ooqbyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vu5ooqbyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-pulse" {...props}></Icon>
