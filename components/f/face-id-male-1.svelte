<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkr_3bbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dkr_3bbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:face-id-male-1" {...props}></Icon>
