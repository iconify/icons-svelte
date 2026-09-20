<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oni2mrusm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oni2mrusm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-big-down-line-filled" {...props}></Icon>
