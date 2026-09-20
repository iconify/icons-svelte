<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqgcnibgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqgcnibgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-n-hexagon-solid" {...props}></Icon>
