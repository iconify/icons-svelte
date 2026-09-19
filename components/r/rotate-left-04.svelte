<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5lrmtgqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5lrmtgqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rotate-left-04" {...props}></Icon>
