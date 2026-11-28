<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ien1wxbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ien1wxbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:gamepad-star" {...props}></Icon>
