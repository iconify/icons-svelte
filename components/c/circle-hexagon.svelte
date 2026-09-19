<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4yh9sqql.css';
import '../../css/a/aps6ewwol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b x4yh9sqql"/><path class="aps6ewwol b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:circle-hexagon" {...props}></Icon>
