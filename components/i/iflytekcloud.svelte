<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xihak6acz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xihak6acz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:iflytekcloud" {...props}></Icon>
