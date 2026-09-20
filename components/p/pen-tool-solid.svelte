<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1x2ahbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="e1x2ahbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:pen-tool-solid" {...props}></Icon>
