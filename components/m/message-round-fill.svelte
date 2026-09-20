<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkh-x7lkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dkh-x7lkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:message-round-fill" {...props}></Icon>
