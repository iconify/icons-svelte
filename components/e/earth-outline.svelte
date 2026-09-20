<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv59azbhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gv59azbhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:earth-outline" {...props}></Icon>
