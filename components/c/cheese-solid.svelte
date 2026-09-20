<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4hj5gzwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q4hj5gzwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cheese-solid" {...props}></Icon>
