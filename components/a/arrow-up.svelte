<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbl1zguft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbl1zguft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-up" {...props}></Icon>
