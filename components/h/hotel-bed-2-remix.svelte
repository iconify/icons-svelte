<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp1v9ybmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sp1v9ybmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:hotel-bed-2-remix" {...props}></Icon>
