<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v50odhb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v50odhb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:keyframe-align-center-filled" {...props}></Icon>
