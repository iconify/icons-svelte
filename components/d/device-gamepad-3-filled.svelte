<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqq0pmbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqq0pmbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-gamepad-3-filled" {...props}></Icon>
