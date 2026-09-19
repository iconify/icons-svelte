<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz4svinmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yz4svinmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:container-services" {...props}></Icon>
