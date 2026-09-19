<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovpu7tbvu.css';
import '../../css/i/iahtnrboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovpu7tbvu"/><path class="iahtnrboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:invert-adjust" {...props}></Icon>
