<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy8owwblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wy8owwblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:meteor-filled" {...props}></Icon>
