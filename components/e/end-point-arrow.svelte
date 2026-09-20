<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjnuvtb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjnuvtb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:end-point-arrow" {...props}></Icon>
