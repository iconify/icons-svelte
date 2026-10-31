<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpr5abczk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpr5abczk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:heart-pulse-fill-round" {...props}></Icon>
