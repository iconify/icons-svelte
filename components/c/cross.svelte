<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozvhalb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozvhalb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:cross" {...props}></Icon>
