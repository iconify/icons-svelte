<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf7qcpbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="mf7qcpbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-vert-small-filled" {...props}></Icon>
