<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ail5k0ifi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ail5k0ifi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:musical-keyboard" {...props}></Icon>
