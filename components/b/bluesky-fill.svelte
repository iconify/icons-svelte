<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oapdrpb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oapdrpb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bluesky-fill" {...props}></Icon>
