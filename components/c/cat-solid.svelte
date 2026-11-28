<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e73-mcctq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e73-mcctq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cat-solid" {...props}></Icon>
