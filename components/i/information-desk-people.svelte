<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k43bmzbdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k43bmzbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:information-desk-people" {...props}></Icon>
