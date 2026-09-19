<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol4ycu_lz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ol4ycu_lz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pound" {...props}></Icon>
