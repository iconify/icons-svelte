<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adzf2_byo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adzf2_byo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:eject-round" {...props}></Icon>
