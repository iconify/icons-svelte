<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s01_cjbkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s01_cjbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nocodb-light" {...props}></Icon>
