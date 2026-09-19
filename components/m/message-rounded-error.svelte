<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-iypzbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-iypzbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:message-rounded-error" {...props}></Icon>
