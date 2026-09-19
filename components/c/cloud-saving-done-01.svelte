<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtma55bwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtma55bwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cloud-saving-done-01" {...props}></Icon>
