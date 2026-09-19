<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y350s-bsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y350s-bsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:package-01" {...props}></Icon>
