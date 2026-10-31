<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m62sktb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m62sktb9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-chevron-double-right-fill-round" {...props}></Icon>
