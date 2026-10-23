<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4sh59bgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4sh59bgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:map" {...props}></Icon>
