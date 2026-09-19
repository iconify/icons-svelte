<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6zi112qj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v6zi112qj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:parallelogram" {...props}></Icon>
