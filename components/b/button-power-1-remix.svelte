<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr5s-2baf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vr5s-2baf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:button-power-1-remix" {...props}></Icon>
