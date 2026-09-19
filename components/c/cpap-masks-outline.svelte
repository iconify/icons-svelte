<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdqw21o2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hdqw21o2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:cpap-masks-outline" {...props}></Icon>
