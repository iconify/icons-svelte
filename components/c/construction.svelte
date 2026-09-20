<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5phmq9_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="w5phmq9_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:construction" {...props}></Icon>
