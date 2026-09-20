<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8h1w9rih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s8h1w9rih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:powerschool" {...props}></Icon>
