<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_3-hbgnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_3-hbgnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-big-right-sharp-duotone" {...props}></Icon>
