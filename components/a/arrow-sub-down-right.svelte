<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhu63-vbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhu63-vbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-sub-down-right" {...props}></Icon>
