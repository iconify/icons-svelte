<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd_2l6tse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qd_2l6tse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:cannabis" {...props}></Icon>
