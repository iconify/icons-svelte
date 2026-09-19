<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9o5d_b6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9o5d_b6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:chevron-down" {...props}></Icon>
