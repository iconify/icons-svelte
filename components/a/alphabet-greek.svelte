<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhpb4hb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhpb4hb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:alphabet-greek" {...props}></Icon>
