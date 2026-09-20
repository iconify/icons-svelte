<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lozx6-brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lozx6-brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mushroom-1-filled" {...props}></Icon>
