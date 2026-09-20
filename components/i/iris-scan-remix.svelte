<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by7dkpbhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="by7dkpbhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:iris-scan-remix" {...props}></Icon>
