<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne_hvlvmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ne_hvlvmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:cable-split-solid" {...props}></Icon>
