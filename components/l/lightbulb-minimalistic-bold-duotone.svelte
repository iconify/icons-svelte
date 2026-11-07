<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht2yptqqj.css';
import '../../css/j/j5ldtz0xa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ht2yptqqj"/><path clip-rule="evenodd" class="j5ldtz0xa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:lightbulb-minimalistic-bold-duotone" {...props}></Icon>
