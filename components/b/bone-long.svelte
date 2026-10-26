<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfshv71lw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rfshv71lw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:bone-long" {...props}></Icon>
