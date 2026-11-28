<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g338unxjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="g338unxjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:rock-tall-fill" {...props}></Icon>
