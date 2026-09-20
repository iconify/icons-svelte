<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcp2bq36g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcp2bq36g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pinterest-line" {...props}></Icon>
