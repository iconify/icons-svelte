<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7dtnxsic.css';
import '../../css/s/sega__bro.css';
import '../../css/v/vmfvg5bti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7dtnxsic"/><path clip-rule="evenodd" class="sega__bro"/><path class="vmfvg5bti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:map-location-solid" {...props}></Icon>
