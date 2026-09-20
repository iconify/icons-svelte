<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs1d7sbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xs1d7sbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:half-star-2-flat" {...props}></Icon>
