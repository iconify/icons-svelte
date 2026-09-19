<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snb_yq7qg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snb_yq7qg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:motion-filled" {...props}></Icon>
