<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue4lfcc1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ue4lfcc1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:more-active" {...props}></Icon>
