<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtc7irb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mtc7irb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:invisible-1-solid" {...props}></Icon>
