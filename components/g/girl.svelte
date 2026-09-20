<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2a0xybtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2a0xybtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:girl" {...props}></Icon>
