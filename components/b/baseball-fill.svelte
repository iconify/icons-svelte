<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sny7_mbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sny7_mbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:baseball-fill" {...props}></Icon>
