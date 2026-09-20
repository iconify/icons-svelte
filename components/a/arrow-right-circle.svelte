<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aemjy9b3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aemjy9b3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-right-circle" {...props}></Icon>
