<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjeec3bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pjeec3bql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cloudron-light" {...props}></Icon>
