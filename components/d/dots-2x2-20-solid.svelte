<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk0g2vbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mk0g2vbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dots-2x2-20-solid" {...props}></Icon>
