<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sac_xsb6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sac_xsb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:letters-i" {...props}></Icon>
