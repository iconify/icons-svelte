<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6ad3mbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6ad3mbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chart-forecast-solid" {...props}></Icon>
