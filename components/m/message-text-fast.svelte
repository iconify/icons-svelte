<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm43j4xee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cm43j4xee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:message-text-fast" {...props}></Icon>
