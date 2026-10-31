<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiwlr94ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aiwlr94ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:plane-takeoff-side-round" {...props}></Icon>
