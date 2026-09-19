<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uswo5nbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uswo5nbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:message-rounded-dots" {...props}></Icon>
