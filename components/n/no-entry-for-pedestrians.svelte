<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bynk47z_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bynk47z_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:no-entry-for-pedestrians" {...props}></Icon>
