<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7q0rkbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":717};
const content = `<path class="v7q0rkbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:globe" {...props}></Icon>
