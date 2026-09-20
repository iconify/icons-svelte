<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlsl8d1ym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qlsl8d1ym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dots-2x3-20-solid" {...props}></Icon>
