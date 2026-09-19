<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugpilfw6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugpilfw6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:greater-than" {...props}></Icon>
