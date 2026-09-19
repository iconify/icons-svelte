<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-q68rezq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="t-q68rezq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:artificial-intelligence2x-outline" {...props}></Icon>
