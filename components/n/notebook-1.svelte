<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxpgxd99y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxpgxd99y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:notebook-1" {...props}></Icon>
