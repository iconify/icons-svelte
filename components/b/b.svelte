<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7o2b8ahf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="g7o2b8ahf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:b" {...props}></Icon>
