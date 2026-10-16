<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-y8ulbyu.css';
import '../../css/x/xovy7qr-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g-y8ulbyu"/><path class="xovy7qr-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-sink-48-bold" {...props}></Icon>
