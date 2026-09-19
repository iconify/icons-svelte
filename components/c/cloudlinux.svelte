<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw_e8kbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uw_e8kbvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:cloudlinux" {...props}></Icon>
