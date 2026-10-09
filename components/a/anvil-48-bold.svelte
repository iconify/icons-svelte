<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x931whbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x931whbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:anvil-48-bold" {...props}></Icon>
