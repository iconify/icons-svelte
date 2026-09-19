<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob3812mib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ob3812mib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:4-outline" {...props}></Icon>
