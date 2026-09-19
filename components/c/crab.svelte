<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm4ce8bws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="vm4ce8bws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:crab" {...props}></Icon>
