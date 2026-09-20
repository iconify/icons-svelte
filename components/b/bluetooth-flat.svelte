<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y10q4sjml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="y10q4sjml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:bluetooth-flat" {...props}></Icon>
