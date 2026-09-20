<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpd8t7b0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wpd8t7b0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:cake-slice-solid" {...props}></Icon>
