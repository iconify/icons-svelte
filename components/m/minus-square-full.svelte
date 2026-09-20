<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq_15b37m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rq_15b37m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:minus-square-full" {...props}></Icon>
