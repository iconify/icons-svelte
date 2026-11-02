<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omwgj_mcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omwgj_mcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:road-fill" {...props}></Icon>
