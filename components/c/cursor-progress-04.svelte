<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxpvowb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxpvowb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cursor-progress-04" {...props}></Icon>
