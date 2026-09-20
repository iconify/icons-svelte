<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r64ihqzvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r64ihqzvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:battery-high" {...props}></Icon>
