<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9g7eebku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9g7eebku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-arrow-right-round" {...props}></Icon>
