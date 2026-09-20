<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpmueccpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lpmueccpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:return-3-remix" {...props}></Icon>
