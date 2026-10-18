<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgigi6f3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgigi6f3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:align-horizontal-distribute-end" {...props}></Icon>
