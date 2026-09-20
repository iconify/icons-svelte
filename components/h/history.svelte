<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl_lzhbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dl_lzhbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:history" {...props}></Icon>
