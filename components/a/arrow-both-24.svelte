<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhn8gh6nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhn8gh6nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-both-24" {...props}></Icon>
