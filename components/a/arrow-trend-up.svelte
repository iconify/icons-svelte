<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyq_gi3cg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyq_gi3cg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:arrow-trend-up" {...props}></Icon>
