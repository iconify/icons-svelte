<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8-gdye2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g8-gdye2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:eraser" {...props}></Icon>
