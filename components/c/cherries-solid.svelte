<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vge3bee0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vge3bee0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:cherries-solid" {...props}></Icon>
