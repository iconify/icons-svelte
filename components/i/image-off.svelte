<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl-t0bawj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sl-t0bawj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:image-off" {...props}></Icon>
