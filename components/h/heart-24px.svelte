<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffmxou07g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffmxou07g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:heart-24px" {...props}></Icon>
