<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8y36bc0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r8y36bc0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:new-folder" {...props}></Icon>
