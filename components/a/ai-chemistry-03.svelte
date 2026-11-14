<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljln6q8iu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljln6q8iu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-chemistry-03" {...props}></Icon>
