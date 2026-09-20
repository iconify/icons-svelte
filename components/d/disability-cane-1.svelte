<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if_2kzbcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="if_2kzbcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:disability-cane-1" {...props}></Icon>
