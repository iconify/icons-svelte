<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plru1qb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="plru1qb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:cam-disk-6k-seg" {...props}></Icon>
