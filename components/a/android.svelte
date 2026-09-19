<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1cnqtbhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1cnqtbhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:android" {...props}></Icon>
