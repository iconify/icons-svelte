<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzvw8wbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzvw8wbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-right-line" {...props}></Icon>
