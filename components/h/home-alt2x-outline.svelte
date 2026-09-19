<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye931s0lu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ye931s0lu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:home-alt2x-outline" {...props}></Icon>
