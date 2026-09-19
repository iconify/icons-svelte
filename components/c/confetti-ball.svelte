<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhpwv3ssp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="vhpwv3ssp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:confetti-ball" {...props}></Icon>
