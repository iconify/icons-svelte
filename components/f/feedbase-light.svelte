<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_zac47mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a_zac47mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:feedbase-light" {...props}></Icon>
