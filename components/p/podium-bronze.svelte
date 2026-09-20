<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pksp8bbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pksp8bbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:podium-bronze" {...props}></Icon>
