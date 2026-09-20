<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yggoe-ujq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yggoe-ujq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:octagon-plus-2" {...props}></Icon>
