<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tudv3wlna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tudv3wlna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chart4" {...props}></Icon>
