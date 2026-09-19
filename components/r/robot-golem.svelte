<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrwb58_hr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wrwb58_hr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:robot-golem" {...props}></Icon>
