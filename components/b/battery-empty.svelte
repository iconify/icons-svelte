<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lai_9vqlp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lai_9vqlp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:battery-empty" {...props}></Icon>
