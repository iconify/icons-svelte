<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9-n70bna.css';
import '../../css/t/tw2nlk24g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9-n70bna"/><path class="tw2nlk24g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-notification-filled" {...props}></Icon>
