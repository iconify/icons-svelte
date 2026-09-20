<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kksua50ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kksua50ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gitsave-light" {...props}></Icon>
