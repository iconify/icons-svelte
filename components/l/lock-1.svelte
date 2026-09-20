<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgzll2bxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xgzll2bxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:lock-1" {...props}></Icon>
