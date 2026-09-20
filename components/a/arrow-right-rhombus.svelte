<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsciwwbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fsciwwbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-right-rhombus" {...props}></Icon>
