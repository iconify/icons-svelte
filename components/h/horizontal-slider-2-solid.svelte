<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atxq1m6er.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="atxq1m6er"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:horizontal-slider-2-solid" {...props}></Icon>
