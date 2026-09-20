<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2dx9kmgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2dx9kmgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:battery-2-charge-line" {...props}></Icon>
