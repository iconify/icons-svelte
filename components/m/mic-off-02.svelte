<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0j2j0bak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0j2j0bak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mic-off-02" {...props}></Icon>
