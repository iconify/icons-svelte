<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xstrmvbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xstrmvbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:notification-active" {...props}></Icon>
