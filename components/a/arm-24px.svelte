<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2u5z701y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2u5z701y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:arm-24px" {...props}></Icon>
