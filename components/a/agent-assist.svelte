<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xchmlgbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xchmlgbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:agent-assist" {...props}></Icon>
