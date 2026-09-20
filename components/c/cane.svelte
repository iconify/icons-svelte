<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1wr4vr1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1wr4vr1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cane" {...props}></Icon>
