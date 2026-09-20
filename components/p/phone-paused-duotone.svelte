<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb7_855gm.css';
import '../../css/o/oieq8dp3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gb7_855gm"/><path class="oieq8dp3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:phone-paused-duotone" {...props}></Icon>
