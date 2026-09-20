<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9jr6ub1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9jr6ub1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:medium" {...props}></Icon>
