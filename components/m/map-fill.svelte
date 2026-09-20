<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrr2rz3sn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrr2rz3sn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:map-fill" {...props}></Icon>
