<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr26pabwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="nr26pabwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:propellor" {...props}></Icon>
