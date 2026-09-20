<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l77vd0brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="l77vd0brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:direction-ltr" {...props}></Icon>
