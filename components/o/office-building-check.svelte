<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq0smd1rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nq0smd1rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:office-building-check" {...props}></Icon>
