<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqwke54yd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pqwke54yd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-contacts" {...props}></Icon>
