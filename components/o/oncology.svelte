<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azivo7bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="azivo7bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:oncology" {...props}></Icon>
