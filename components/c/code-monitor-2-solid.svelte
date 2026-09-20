<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnkczcb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lnkczcb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:code-monitor-2-solid" {...props}></Icon>
