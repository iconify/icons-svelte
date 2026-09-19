<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s17m2ib-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s17m2ib-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:crunchyroll" {...props}></Icon>
