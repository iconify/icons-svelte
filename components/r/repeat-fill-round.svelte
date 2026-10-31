<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-r5fg3qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-r5fg3qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:repeat-fill-round" {...props}></Icon>
