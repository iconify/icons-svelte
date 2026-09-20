<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0a_25-9h.css';
import '../../css/m/mfxe6gbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0a_25-9h"/><path class="mfxe6gbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:archive-24" {...props}></Icon>
