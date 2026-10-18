<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saot2obzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="saot2obzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:message-square-more" {...props}></Icon>
