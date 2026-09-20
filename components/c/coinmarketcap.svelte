<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1lz7zpzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g1lz7zpzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:coinmarketcap" {...props}></Icon>
