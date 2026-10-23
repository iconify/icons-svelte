<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2e40ccms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2e40ccms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:map-pin-minus" {...props}></Icon>
