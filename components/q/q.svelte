<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhx0khm2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rhx0khm2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:q" {...props}></Icon>
