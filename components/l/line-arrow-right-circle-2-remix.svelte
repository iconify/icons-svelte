<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns9--7zyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ns9--7zyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:line-arrow-right-circle-2-remix" {...props}></Icon>
