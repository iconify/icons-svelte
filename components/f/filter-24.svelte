<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x42navb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x42navb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:filter-24" {...props}></Icon>
