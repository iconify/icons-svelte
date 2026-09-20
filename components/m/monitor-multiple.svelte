<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5lmjr0_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5lmjr0_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:monitor-multiple" {...props}></Icon>
