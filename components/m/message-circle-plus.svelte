<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykj3jqd3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykj3jqd3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-circle-plus" {...props}></Icon>
