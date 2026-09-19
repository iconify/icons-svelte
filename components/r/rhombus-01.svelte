<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr1rmrbnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pr1rmrbnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rhombus-01" {...props}></Icon>
