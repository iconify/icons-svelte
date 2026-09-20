<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk577i3vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pk577i3vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:helicopter-landing-filled" {...props}></Icon>
