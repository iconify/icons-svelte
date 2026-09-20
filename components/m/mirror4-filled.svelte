<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg4wobcpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fg4wobcpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mirror4-filled" {...props}></Icon>
