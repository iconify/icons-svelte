<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tucwv7bnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="tucwv7bnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:helicopter-fill" {...props}></Icon>
