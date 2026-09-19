<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd89w8b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rd89w8b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:moon-phase-2" {...props}></Icon>
