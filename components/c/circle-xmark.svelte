<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da-5a4b7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="da-5a4b7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:circle-xmark" {...props}></Icon>
