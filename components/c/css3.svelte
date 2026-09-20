<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l12kxsblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l12kxsblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:css3" {...props}></Icon>
