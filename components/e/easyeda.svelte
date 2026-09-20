<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csi0gx22s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csi0gx22s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:easyeda" {...props}></Icon>
