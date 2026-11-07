<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owtnwjtgw.css';
import '../../css/w/wmja1bbmm.css';
import '../../css/b/beswcrb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owtnwjtgw"/><path class="wmja1bbmm"/><path clip-rule="evenodd" class="beswcrb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cup-first-bold" {...props}></Icon>
