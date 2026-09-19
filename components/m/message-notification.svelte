<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et211dbdf.css';
import '../../css/a/a9-n70bna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="et211dbdf"/><path class="a9-n70bna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-notification" {...props}></Icon>
