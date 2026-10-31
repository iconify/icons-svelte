<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugp6xac2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugp6xac2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:redo-duocolor-round" {...props}></Icon>
