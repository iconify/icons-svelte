<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztzi5bcmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztzi5bcmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:dolphin-dphnai" {...props}></Icon>
