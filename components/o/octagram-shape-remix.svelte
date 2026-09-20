<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msg05sbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="msg05sbqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:octagram-shape-remix" {...props}></Icon>
