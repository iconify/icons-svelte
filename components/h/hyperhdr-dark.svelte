<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eve3a1jad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eve3a1jad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hyperhdr-dark" {...props}></Icon>
