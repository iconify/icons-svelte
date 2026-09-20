<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rocomobfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rocomobfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:more-muted-vert-square-line" {...props}></Icon>
