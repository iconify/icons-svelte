<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg3_7vbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tg3_7vbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:credit-card" {...props}></Icon>
