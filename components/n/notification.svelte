<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhwbso37e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhwbso37e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:notification" {...props}></Icon>
