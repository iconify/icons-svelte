<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgu5rybei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgu5rybei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:plane-inflight" {...props}></Icon>
