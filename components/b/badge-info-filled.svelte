<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy0s7rb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sy0s7rb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:badge-info-filled" {...props}></Icon>
