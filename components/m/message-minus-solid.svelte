<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp_83_ara.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lp_83_ara"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:message-minus-solid" {...props}></Icon>
