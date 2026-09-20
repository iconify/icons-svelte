<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njpbjcc-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njpbjcc-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mini-program-line" {...props}></Icon>
