<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvj36pv6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="mvj36pv6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:flask" {...props}></Icon>
