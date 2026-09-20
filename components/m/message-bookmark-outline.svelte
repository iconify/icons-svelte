<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-gmybyap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-gmybyap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:message-bookmark-outline" {...props}></Icon>
