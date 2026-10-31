<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9nh01drz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9nh01drz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-arrow-down-right-round" {...props}></Icon>
