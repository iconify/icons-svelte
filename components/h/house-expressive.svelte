<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jiv8c9bhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jiv8c9bhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:house-expressive" {...props}></Icon>
