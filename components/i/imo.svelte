<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz2527jze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sz2527jze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:imo" {...props}></Icon>
