<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5le61biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5le61biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:message-round-square-fill" {...props}></Icon>
