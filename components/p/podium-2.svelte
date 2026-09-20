<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_nh699rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_nh699rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:podium-2" {...props}></Icon>
