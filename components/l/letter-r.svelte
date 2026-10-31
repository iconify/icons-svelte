<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7q0o6bdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7q0o6bdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:letter-r" {...props}></Icon>
