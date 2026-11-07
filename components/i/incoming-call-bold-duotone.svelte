<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjrrq5bwn.css';
import '../../css/j/j05r12o9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjrrq5bwn"/><path class="j05r12o9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:incoming-call-bold-duotone" {...props}></Icon>
