<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvo3i_ynj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvo3i_ynj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:chart" {...props}></Icon>
