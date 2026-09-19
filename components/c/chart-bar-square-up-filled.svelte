<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7dx4lb0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7dx4lb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chart-bar-square-up-filled" {...props}></Icon>
