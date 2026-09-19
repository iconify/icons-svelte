<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt117bbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gt117bbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:moon-phase-2-filled" {...props}></Icon>
