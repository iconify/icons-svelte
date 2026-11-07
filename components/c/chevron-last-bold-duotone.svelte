<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwow_w44a.css';
import '../../css/l/lsq66r8ar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwow_w44a"/><path class="lsq66r8ar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevron-last-bold-duotone" {...props}></Icon>
