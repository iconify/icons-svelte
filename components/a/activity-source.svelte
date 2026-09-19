<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8--ehbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s8--ehbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:activity-source" {...props}></Icon>
