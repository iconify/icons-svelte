<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li4ol9huc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="li4ol9huc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:dark-sunglasses" {...props}></Icon>
