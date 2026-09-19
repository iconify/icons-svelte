<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-8pg3yxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m-8pg3yxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:autotask" {...props}></Icon>
