<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtvm8qbid.css';
import '../../css/n/n1vzbldsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vtvm8qbid"/><path class="n1vzbldsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrows-horizontal-48-bold" {...props}></Icon>
