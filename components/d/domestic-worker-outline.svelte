<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe8iz054p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="oe8iz054p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:domestic-worker-outline" {...props}></Icon>
