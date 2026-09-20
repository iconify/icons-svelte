<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2pr8qhck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y2pr8qhck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:egg-filled" {...props}></Icon>
