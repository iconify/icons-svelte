<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5mb7ejud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="r5mb7ejud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:add-layer-2-solid" {...props}></Icon>
