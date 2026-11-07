<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvude-bvd.css';
import '../../css/r/rgo0fe4hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvude-bvd"/><path class="rgo0fe4hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:armchair-bold-duotone" {...props}></Icon>
