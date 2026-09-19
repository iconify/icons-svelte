<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9-xtjkga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y9-xtjkga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-regular" {...props}></Icon>
