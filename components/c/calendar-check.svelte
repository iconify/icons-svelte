<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp687xbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qp687xbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:calendar-check" {...props}></Icon>
