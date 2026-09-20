<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7q32y5jl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v7q32y5jl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:flash-1-solid" {...props}></Icon>
