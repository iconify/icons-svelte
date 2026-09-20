<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg567jbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vg567jbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:loading-circle-solid" {...props}></Icon>
