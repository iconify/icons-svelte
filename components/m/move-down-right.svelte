<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga5l93quz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ga5l93quz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:move-down-right" {...props}></Icon>
