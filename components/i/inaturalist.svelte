<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5r6_0skh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="z5r6_0skh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:inaturalist" {...props}></Icon>
