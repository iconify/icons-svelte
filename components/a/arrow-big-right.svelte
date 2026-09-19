<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxwbqd-fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxwbqd-fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-big-right" {...props}></Icon>
