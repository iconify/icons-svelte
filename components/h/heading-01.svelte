<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da52_eirn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="da52_eirn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:heading-01" {...props}></Icon>
