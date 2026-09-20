<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4t2n67if.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4t2n67if"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heart-slash-solid" {...props}></Icon>
