<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bexrkib9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bexrkib9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-move-right-x" {...props}></Icon>
