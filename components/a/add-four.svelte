<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir6w98bve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ir6w98bve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:add-four" {...props}></Icon>
