<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddwiuu_lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b ddwiuu_lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:reading-glass-filled" {...props}></Icon>
