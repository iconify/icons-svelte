<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwylracsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwylracsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:patch-fixes" {...props}></Icon>
