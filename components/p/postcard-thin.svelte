<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayhnhab8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ayhnhab8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:postcard-thin" {...props}></Icon>
