<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nod0a6b7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nod0a6b7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-loss-48" {...props}></Icon>
