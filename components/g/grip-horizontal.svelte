<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-ha4xbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-ha4xbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:grip-horizontal" {...props}></Icon>
