<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swgmve7ca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swgmve7ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:arrow-circle-right" {...props}></Icon>
