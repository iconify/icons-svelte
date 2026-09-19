<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p03ohdb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p03ohdb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:galactic-senate" {...props}></Icon>
