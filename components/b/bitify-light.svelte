<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fat_n_bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fat_n_bql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bitify-light" {...props}></Icon>
