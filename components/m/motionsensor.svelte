<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvw8wccdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvw8wccdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:motionsensor" {...props}></Icon>
