<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr9kdcb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yr9kdcb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:circle-dot" {...props}></Icon>
