<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfquunxwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfquunxwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:message-check-round-fill" {...props}></Icon>
