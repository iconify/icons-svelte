<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv6y-3b6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="dv6y-3b6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:android" {...props}></Icon>
