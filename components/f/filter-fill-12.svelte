<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vekcsdd2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="vekcsdd2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:filter-fill-12" {...props}></Icon>
