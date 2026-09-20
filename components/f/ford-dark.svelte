<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgi78ebgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sgi78ebgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ford-dark" {...props}></Icon>
