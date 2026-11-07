<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjrrq5bwn.css';
import '../../css/s/s02o69bfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjrrq5bwn"/><path class="s02o69bfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:incoming-call-rounded-bold-duotone" {...props}></Icon>
