<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjke9fltu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pjke9fltu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:import-all-mirrored" {...props}></Icon>
