<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw2n-_wlj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gw2n-_wlj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:human-resources-workflow-bold" {...props}></Icon>
