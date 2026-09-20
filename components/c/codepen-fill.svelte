<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svpdh13sp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svpdh13sp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:codepen-fill" {...props}></Icon>
