<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4g5wbp8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4g5wbp8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-up2" {...props}></Icon>
