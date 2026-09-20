<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk_s0qb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hk_s0qb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:relic-storage-dark" {...props}></Icon>
