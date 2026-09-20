<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-g4x1p4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e-g4x1p4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:hardware-tv" {...props}></Icon>
