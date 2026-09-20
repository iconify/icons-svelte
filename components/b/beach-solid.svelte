<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-01g7bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="e-01g7bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:beach-solid" {...props}></Icon>
