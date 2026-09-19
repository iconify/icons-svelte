<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq665t1ax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qq665t1ax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:anchor" {...props}></Icon>
