<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwfsk8xgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fwfsk8xgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:pagelines" {...props}></Icon>
