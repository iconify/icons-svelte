<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu9cxub5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iu9cxub5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:robot-vacuum-variant" {...props}></Icon>
