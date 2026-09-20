<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orjwlbbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="orjwlbbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:photoprism-dark" {...props}></Icon>
