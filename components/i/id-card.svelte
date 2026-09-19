<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovi425ott.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovi425ott"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:id-card" {...props}></Icon>
