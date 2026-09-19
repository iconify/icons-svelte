<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8xonz-pr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8xonz-pr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:kurta-01" {...props}></Icon>
