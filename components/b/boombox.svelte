<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw74o5bvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hw74o5bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:boombox" {...props}></Icon>
