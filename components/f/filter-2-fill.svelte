<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnosb5bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnosb5bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:filter-2-fill" {...props}></Icon>
