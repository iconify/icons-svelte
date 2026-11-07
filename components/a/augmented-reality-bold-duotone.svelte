<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg928d-qd.css';
import '../../css/a/a-44o5enj.css';
import '../../css/w/wn9x1iaaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg928d-qd"/><path clip-rule="evenodd" class="a-44o5enj"/><path clip-rule="evenodd" class="wn9x1iaaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:augmented-reality-bold-duotone" {...props}></Icon>
